<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cndsmi0bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cndsmi0bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:social-whatsapp-solid" {...props}></Icon>
