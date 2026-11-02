<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6n0wxk8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6n0wxk8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:table-2-fill" {...props}></Icon>
