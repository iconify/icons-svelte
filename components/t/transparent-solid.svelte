<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezzmhybor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ezzmhybor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:transparent-solid" {...props}></Icon>
