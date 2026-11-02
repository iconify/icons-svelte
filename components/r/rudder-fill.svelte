<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo7x2ac5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo7x2ac5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rudder-fill" {...props}></Icon>
