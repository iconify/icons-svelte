<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd6ddu7-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd6ddu7-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:seafile" {...props}></Icon>
