<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae1i43b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae1i43b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:temperature-sun" {...props}></Icon>
