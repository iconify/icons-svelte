<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k12o0ub5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k12o0ub5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:star" {...props}></Icon>
