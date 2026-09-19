<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vljrm96wr.css';
import '../../css/j/ju7w-1bcy.css';
import '../../css/s/s7iuqsm4j.css';
import '../../css/o/oxztbklch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vljrm96wr"/><path clip-rule="evenodd" class="ju7w-1bcy"/><path class="s7iuqsm4j"/><path clip-rule="evenodd" class="oxztbklch"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:tg" {...props}></Icon>
