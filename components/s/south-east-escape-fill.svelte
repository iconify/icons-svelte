<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fix_3rbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fix_3rbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:south-east-escape-fill" {...props}></Icon>
