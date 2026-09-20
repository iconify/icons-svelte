<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v89yi071i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v89yi071i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zoom" {...props}></Icon>
