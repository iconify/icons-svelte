<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq3pivbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="bq3pivbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:vuejs" {...props}></Icon>
