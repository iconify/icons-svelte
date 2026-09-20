<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynf4fk1jh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path class="ynf4fk1jh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sign-out" {...props}></Icon>
