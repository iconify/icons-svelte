<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh8ehk5lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oh8ehk5lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:signal" {...props}></Icon>
