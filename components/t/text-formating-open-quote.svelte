<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b07l3eb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b07l3eb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:text-formating-open-quote" {...props}></Icon>
