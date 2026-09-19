<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab-b74q4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ab-b74q4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:settings-adjust-outline" {...props}></Icon>
