<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7yggfbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="n7yggfbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:sun-cloud-filled" {...props}></Icon>
