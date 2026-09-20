<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bukq1mb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bukq1mb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:server-2-fill" {...props}></Icon>
