<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de2mo0bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="de2mo0bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:support" {...props}></Icon>
