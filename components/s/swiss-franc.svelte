<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7fm4ccbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7fm4ccbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:swiss-franc" {...props}></Icon>
