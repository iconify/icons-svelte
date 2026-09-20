<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3qd3j95h.css';
import '../../css/r/rixxe_b4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3qd3j95h"/><path class="rixxe_b4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:unlock-alt" {...props}></Icon>
