<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv1g0uw2g.css';
import '../../css/p/phh4k69ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sv1g0uw2g"/><path class="phh4k69ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:user-plus-outline" {...props}></Icon>
