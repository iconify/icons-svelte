<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yot74wbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yot74wbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sunset-fill" {...props}></Icon>
