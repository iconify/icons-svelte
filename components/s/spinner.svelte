<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghi9fqb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghi9fqb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:spinner" {...props}></Icon>
