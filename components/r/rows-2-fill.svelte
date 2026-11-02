<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brzb2eb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brzb2eb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rows-2-fill" {...props}></Icon>
