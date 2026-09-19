<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya8morbtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya8morbtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:send" {...props}></Icon>
