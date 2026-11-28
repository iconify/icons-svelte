<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oche6t6ju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oche6t6ju primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:semicolon-duotone" {...props}></Icon>
