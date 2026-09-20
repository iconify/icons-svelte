<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1p4edmlk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1p4edmlk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:wallet-sharp" {...props}></Icon>
