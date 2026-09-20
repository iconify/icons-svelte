<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe9ard3ii.css';
import '../../css/o/o2ezd7b3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe9ard3ii"/><path class="o2ezd7b3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:sign-in-alt" {...props}></Icon>
