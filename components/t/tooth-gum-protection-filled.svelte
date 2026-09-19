<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1x18obir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x1x18obir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tooth-gum-protection-filled" {...props}></Icon>
