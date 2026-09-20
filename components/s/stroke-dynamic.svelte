<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5unneb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5unneb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:stroke-dynamic" {...props}></Icon>
