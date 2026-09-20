<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojg7gdc0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojg7gdc0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:skype" {...props}></Icon>
