<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o47u3jkre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o47u3jkre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:science-fill" {...props}></Icon>
