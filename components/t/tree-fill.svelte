<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iscz7hbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iscz7hbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tree-fill" {...props}></Icon>
