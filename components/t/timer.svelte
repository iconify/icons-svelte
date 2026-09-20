<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfn7lsbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfn7lsbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:timer" {...props}></Icon>
