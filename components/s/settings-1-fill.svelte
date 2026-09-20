<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im8enibwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="im8enibwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-1-fill" {...props}></Icon>
