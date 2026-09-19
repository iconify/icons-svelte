<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zdieb42co.css';
import '../../css/s/s1nbg9lfp.css';
import '../../css/l/l5dtm8qih.css';
import '../../css/r/rxlbqwg2m.css';
import '../../css/l/lvjbzjcnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="zdieb42co"/><path class="s1nbg9lfp"/><path clip-rule="evenodd" class="l5dtm8qih"/><path class="rxlbqwg2m"/><path class="lvjbzjcnh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:trophy" {...props}></Icon>
