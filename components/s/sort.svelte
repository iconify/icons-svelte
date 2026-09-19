<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz-nt3jcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jz-nt3jcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:sort" {...props}></Icon>
