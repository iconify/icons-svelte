<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upoh5b8jj.css';
import '../../css/d/dca1hzb9h.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/z/zvlp41bor.css';
import '../../css/e/el7kd0g5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="upoh5b8jj"/><path class="dca1hzb9h"/><g class="jn8qy4bru"><path class="zvlp41bor"/><path class="el7kd0g5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:salt-mill" {...props}></Icon>
