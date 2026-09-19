<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c65rc4bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c65rc4bgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:terminal" {...props}></Icon>
