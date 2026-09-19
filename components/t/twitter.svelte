<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps0hlobzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ps0hlobzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:twitter" {...props}></Icon>
