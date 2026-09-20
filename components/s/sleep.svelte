<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-kj6cbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-kj6cbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:sleep" {...props}></Icon>
