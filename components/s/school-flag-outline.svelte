<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noee0qjqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="noee0qjqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:school-flag-outline" {...props}></Icon>
