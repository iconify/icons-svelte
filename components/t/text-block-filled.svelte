<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae-3ksbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae-3ksbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:text-block-filled" {...props}></Icon>
