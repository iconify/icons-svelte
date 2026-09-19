<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrfc46b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vrfc46b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:shape-triangle" {...props}></Icon>
