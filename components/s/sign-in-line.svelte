<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok5q6j3op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ok5q6j3op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:sign-in-line" {...props}></Icon>
