<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auouaz90v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auouaz90v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:sun-outline" {...props}></Icon>
