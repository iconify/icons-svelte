<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu6q7vpel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu6q7vpel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:surprise" {...props}></Icon>
