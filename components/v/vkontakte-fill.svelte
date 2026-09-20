<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkyvmsbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkyvmsbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vkontakte-fill" {...props}></Icon>
