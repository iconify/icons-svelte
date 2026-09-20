<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd23m8brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gd23m8brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:star-fill" {...props}></Icon>
