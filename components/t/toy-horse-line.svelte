<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs-apjbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xs-apjbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:toy-horse-line" {...props}></Icon>
