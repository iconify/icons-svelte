<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/u/uqiqh7wda.css';
import '../../css/n/n-s3_4imp.css';
import '../../css/n/n3murebba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uqiqh7wda"/><circle class="n-s3_4imp"/><path class="n3murebba"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:search-slash" {...props}></Icon>
