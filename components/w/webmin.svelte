<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w701jtbjt.css';
import '../../css/j/j8w5bp6yw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w701jtbjt"/><path class="j8w5bp6yw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:webmin" {...props}></Icon>
