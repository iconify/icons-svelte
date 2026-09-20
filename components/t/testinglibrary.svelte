<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3iwq-bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3iwq-bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:testinglibrary" {...props}></Icon>
