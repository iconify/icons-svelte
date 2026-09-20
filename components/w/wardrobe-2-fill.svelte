<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glpwanriu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glpwanriu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wardrobe-2-fill" {...props}></Icon>
