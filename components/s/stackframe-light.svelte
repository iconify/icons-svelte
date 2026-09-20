<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsh_v_bre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsh_v_bre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:stackframe-light" {...props}></Icon>
