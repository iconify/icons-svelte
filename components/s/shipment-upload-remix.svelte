<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odzm6z18x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="odzm6z18x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:shipment-upload-remix" {...props}></Icon>
