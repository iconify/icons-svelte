<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne8y8bu0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ne8y8bu0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:scalpel-filled" {...props}></Icon>
