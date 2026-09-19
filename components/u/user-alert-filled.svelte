<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnhup6rke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mnhup6rke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:user-alert-filled" {...props}></Icon>
