<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee8z-20zw.css';
import '../../css/m/m-327hb7l.css';
import '../../css/q/qpyv20i8g.css';
import '../../css/l/ljqckqbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee8z-20zw"/><path class="m-327hb7l"/><path class="qpyv20i8g"/><path class="ljqckqbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:wliti" {...props}></Icon>
