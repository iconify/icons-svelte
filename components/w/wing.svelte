<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7ywrlbnk.css';
import '../../css/p/p0jv7ib7i.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/t/tu2z8fb9g.css';
import '../../css/e/e9rmuj2zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="m7ywrlbnk"/><path class="p0jv7ib7i"/><g class="jn8qy4bru"><path class="tu2z8fb9g"/><path class="e9rmuj2zs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:wing" {...props}></Icon>
