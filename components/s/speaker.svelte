<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn58-rbyn.css';
import '../../css/i/ihuhp8x1t.css';
import '../../css/f/f4v_liz2h.css';
import '../../css/t/tmksm5bqd.css';
import '../../css/p/poqn3h4kh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pn58-rbyn"/><path class="ihuhp8x1t"/><path class="f4v_liz2h"/><path class="tmksm5bqd"/><path class="poqn3h4kh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:speaker" {...props}></Icon>
