<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/o/o1yqvdbsu.css';
import '../../css/t/tmb8qfb1t.css';
import '../../css/g/gjjdxf-5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o1yqvdbsu"/><path class="tmb8qfb1t"/><path class="gjjdxf-5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shop5" {...props}></Icon>
