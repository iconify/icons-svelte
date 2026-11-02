<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch6k0bq6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ch6k0bq6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:utensils-fill" {...props}></Icon>
