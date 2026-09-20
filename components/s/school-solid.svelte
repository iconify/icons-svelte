<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9eokvp7t.css';
import '../../css/w/w17inbchm.css';
import '../../css/u/uuguc0g7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v9eokvp7t"/><path clip-rule="evenodd" class="w17inbchm"/><path class="uuguc0g7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:school-solid" {...props}></Icon>
