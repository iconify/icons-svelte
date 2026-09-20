<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b47299ewv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b47299ewv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:thumbs-up-sharp" {...props}></Icon>
