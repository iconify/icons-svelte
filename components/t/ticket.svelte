<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7jwm8e_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7jwm8e_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:ticket" {...props}></Icon>
