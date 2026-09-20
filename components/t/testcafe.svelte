<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs_njs9ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fs_njs9ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:testcafe" {...props}></Icon>
