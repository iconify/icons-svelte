<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r795t1bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r795t1bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:rubocop" {...props}></Icon>
