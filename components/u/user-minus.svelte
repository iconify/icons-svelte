<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbeaf3bzp.css';
import '../../css/b/b3jjboblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jbeaf3bzp"/><path class="b3jjboblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-minus" {...props}></Icon>
