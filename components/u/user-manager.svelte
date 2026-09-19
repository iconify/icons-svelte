<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfku7l3wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfku7l3wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:user-manager" {...props}></Icon>
