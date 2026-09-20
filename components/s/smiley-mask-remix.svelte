<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq2o04i_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gq2o04i_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smiley-mask-remix" {...props}></Icon>
