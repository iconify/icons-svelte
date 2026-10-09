<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0gei6bou.css';
import '../../css/d/dztgh4bcl.css';
import '../../css/b/b1sfwsxyj.css';
import '../../css/a/alivzijug.css';
import '../../css/c/c4tbdll5w.css';
import '../../css/z/zs372kprb.css';
import '../../css/l/l338p9bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f0gei6bou"/><path class="dztgh4bcl"/><path class="b1sfwsxyj"/><path class="alivzijug"/><path class="c4tbdll5w"/><path class="zs372kprb"/><path class="l338p9bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-turbine-check-48-bold" {...props}></Icon>
