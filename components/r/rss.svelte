<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s40gp385v.css';
import '../../css/h/hntz4fq6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s40gp385v"/><circle class="hntz4fq6i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:rss" {...props}></Icon>
