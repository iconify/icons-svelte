<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx2_beb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx2_beb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:umbrella-alt-02-filled" {...props}></Icon>
