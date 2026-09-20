<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h090gtm4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="h090gtm4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:user-protection-check-solid" {...props}></Icon>
