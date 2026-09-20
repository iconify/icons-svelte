<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsxj7eb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zsxj7eb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:winmate" {...props}></Icon>
