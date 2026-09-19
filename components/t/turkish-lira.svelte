<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egq4n-0ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egq4n-0ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:turkish-lira" {...props}></Icon>
