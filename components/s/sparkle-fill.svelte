<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_mc30q-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_mc30q-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sparkle-fill" {...props}></Icon>
