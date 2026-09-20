<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6kbyabhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6kbyabhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:stagetimer" {...props}></Icon>
