<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm4bc-bnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm4bc-bnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:shield" {...props}></Icon>
