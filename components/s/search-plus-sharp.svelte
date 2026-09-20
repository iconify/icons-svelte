<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbi2j8bjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbi2j8bjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:search-plus-sharp" {...props}></Icon>
