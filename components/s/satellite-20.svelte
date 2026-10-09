<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2bhn2v8h.css';
import '../../css/w/whvapjd8j.css';
import '../../css/o/o_af29byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u2bhn2v8h"/><path class="whvapjd8j"/><path class="o_af29byo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:satellite-20" {...props}></Icon>
