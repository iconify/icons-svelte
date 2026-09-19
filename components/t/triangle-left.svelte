<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmi1g064l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xmi1g064l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:triangle-left" {...props}></Icon>
