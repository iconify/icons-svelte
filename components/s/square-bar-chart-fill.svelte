<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu6ww8f0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fu6ww8f0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-bar-chart-fill" {...props}></Icon>
