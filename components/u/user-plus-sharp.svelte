<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1anwyqzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1anwyqzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:user-plus-sharp" {...props}></Icon>
