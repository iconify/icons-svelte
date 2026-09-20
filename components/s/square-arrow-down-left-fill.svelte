<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq6g3fbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gq6g3fbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-down-left-fill" {...props}></Icon>
