<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b__vzjb9s.css';
import '../../css/t/tvb2i4bux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b__vzjb9s"/><path class="tvb2i4bux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:shop-duotone" {...props}></Icon>
