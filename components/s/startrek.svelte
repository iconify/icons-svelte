<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myx4-abjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myx4-abjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:startrek" {...props}></Icon>
