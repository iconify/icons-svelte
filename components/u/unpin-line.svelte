<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7rc0abjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7rc0abjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:unpin-line" {...props}></Icon>
