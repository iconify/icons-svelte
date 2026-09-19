<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkh3mii8l.css';
import '../../css/w/w4ucru71v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkh3mii8l"/><path class="w4ucru71v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:temple-filled" {...props}></Icon>
