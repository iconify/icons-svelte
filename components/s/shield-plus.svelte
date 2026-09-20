<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfkh3qbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfkh3qbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:shield-plus" {...props}></Icon>
