<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy7aaeaqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dy7aaeaqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sofa2" {...props}></Icon>
