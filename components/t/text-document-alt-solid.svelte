<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phivkab6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="phivkab6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:text-document-alt-solid" {...props}></Icon>
