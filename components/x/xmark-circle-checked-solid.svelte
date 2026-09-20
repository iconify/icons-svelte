<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3cgnmb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v3cgnmb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:xmark-circle-checked-solid" {...props}></Icon>
