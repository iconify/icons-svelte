<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkacgwkry.css';
import '../../css/g/gilleue9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkacgwkry"/><path class="gilleue9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shop-like-bold" {...props}></Icon>
