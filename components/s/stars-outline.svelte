<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsz2wpbpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rsz2wpbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stars-outline" {...props}></Icon>
