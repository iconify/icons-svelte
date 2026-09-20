<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymlmo2owc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ymlmo2owc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:tick-circle-solid" {...props}></Icon>
