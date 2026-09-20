<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upq7dqbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="upq7dqbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:tailwindcss" {...props}></Icon>
