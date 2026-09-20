<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhle38bke.css';
import '../../css/f/fsl5_2myu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qhle38bke"/><path class="fsl5_2myu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xet" {...props}></Icon>
