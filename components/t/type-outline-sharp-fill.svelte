<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-kylhbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n-kylhbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:type-outline-sharp-fill" {...props}></Icon>
