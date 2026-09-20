<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5qn53n-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"top":-1.5};
const content = `<path class="b5qn53n-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:tools-f" {...props}></Icon>
