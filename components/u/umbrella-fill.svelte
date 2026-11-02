<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0ckdqbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0ckdqbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:umbrella-fill" {...props}></Icon>
