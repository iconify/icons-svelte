<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltj7jfb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltj7jfb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:star-half-fill" {...props}></Icon>
