<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwsxb2bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwsxb2bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:shield" {...props}></Icon>
