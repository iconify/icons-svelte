<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu2fvpofx.css';
import '../../css/b/bqv8f3bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bu2fvpofx"/><path clip-rule="evenodd" class="bqv8f3bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:task-16" {...props}></Icon>
