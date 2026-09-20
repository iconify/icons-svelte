<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m14nbmsbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m14nbmsbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:work-item-issue" {...props}></Icon>
