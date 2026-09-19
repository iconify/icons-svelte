<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frd6sbckt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frd6sbckt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:user-edit-outline" {...props}></Icon>
