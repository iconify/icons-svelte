<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj0feoo2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aj0feoo2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:seat-child-filled" {...props}></Icon>
