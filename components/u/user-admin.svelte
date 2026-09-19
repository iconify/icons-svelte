<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9kkqxb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9kkqxb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:user-admin" {...props}></Icon>
