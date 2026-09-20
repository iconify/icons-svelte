<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/b4zutccum.css';
import '../../css/j/jxq-gfbkl.css';
import '../../css/k/ku8s4lbtf.css';
import '../../css/z/z9ksytbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b4zutccum"/><path class="jxq-gfbkl"/><path class="ku8s4lbtf"/><path class="z9ksytbzl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:widget-2-linear" {...props}></Icon>
